# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2bfc7cadbd52a90833416633a77ce1941086ea79',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'b02737a0783ae7e40c728f9b346aa919c241f270',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '50bc4debdc3eec5045edbeb8ce164090e29b91f3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5b98dea6f1ce1a6b84d733d6093cdb208f4a0752',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd91597a82f881d473887b560a03a7edf2720b72c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1a337fe32d4d5be2ec2af7e02647005aeb358faa',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'eb9b6043be165f06c7ec78fadbb1ff773c5fc19c',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'bfd85956e1b4c1c79842ce857fc7fb15adb8a573',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'cbce9f2487b98c280d145dbed34e82e2ab4b77d8',
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
