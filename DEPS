# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f69d2768e534132e8626c4817c80e95464dcda8e',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5d4562d56eb3cc8ac23f70fd48e549d0751b2fde',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'a62b032007b2e7a69f24a195cbfbd0cf22d31bb0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ada92f84927350c8f3567a06e23e4ff2b04f6810',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '14345dab231912ee9601136e96ca67a6e1f632e7',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8bdce6d842ca9f9bd0a4119963b0eb10693f5b23',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6991ccb68890681b1a3e0f56acd8f53b20ad1e79',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '8c907ea21fe0147f791d79051b18e21bc8c4ede0',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e338b251211a98b3c31ff9090d2fb502fe0b4bf9',
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
