# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '05cfcc1613c28c1274036f53616d66324f7cd383',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e088d553426a3036270701d07dde28bf33d318be',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '50daff941d88609b4d2ad076eae558e727f8e5cd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e0bad2825dacf274578ec6d3c0e64e406d5e4fd7',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b39ab380a44b6c8df462c34e976ea9ce2d2c336b',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '63b05d2b087952662623de7eddd44f2e57d71a1e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'fbe722654b7173da961398cf78bd4a62d1839b65',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'e48ae20a7938b01aee62806bfcdafe8a0883b1e4',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '07f0c3e0505802b4781608ea8f3e639c6f0d6018',
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
