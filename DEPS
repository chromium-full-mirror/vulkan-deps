# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a0995c49ebcaca2c6d3b03efbabf74f3843decdb',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '4e9bb6f426cf776910848441da65cc14f1146e77',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '36d5e2ddaa54c70d2f29081510c66f4fc98e5e53',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3fb52548bc8a68d349d31e21bd4e80e3d953e87c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '49af1bfe467dd5a9efc22f7867d95fdde50e2b00',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ce2d68b24b66a91ed798d870ca205f899ee6e79d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a2224abf350f61211462a33e5b540201fa17de0d',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'b538fb5b08513aa78346cd414ad5e576a2a3e920',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8d636904694c0d93085f373da8336e4dbf98b8df',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
